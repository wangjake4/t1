代发 wailian999

C#:   Debug.Assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2btaltmbd.html

[H08] 获取错误信息与堆栈
来源：http://dali.svipenyu.cn/Article/details/gt2lvrdzldp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cucudq.cn/Article/details/gt2cralznwg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shzxlz.cn/Article/details/gt2kdocegxo.html

JS:   e.message;  e.stack
来源：http://dali.fengsongda.top/Article/details/gt2sptbnlie.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cucudq.cn/Article/details/gt2gpxfizgi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.pengpengdd.cyou/Article/details/gt2mryexbbp.html

Go:   err.Error()
来源：http://dali.jiagoushi.top/Article/details/gt2pjbomwhf.html

Ruby: e.message;  e.backtrace
来源：http://dali.daxiang520.top/Article/details/gt2fqaaectm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shuidangran.top/Article/details/gt2outnuint.html

[H09] 带错误码的异常
来源：http://dali.iojbl.cn/Article/details/gt2sksxmqad.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.kuanghao11.cn/Article/details/gt2zuwarcnr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gogol.net.cn/Article/details/gt2ffxniywa.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pycfn.com/Article/details/gt2cunmirim.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wtxsxnmk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cheryme.top/Article/details/gt2dooishnk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daxiang520.top/Article/details/gt2uqujvwpw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.0kj1m.cn/Article/details/gt2aasqpocd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tianlin.xyz/Article/details/gt2wuskehvj.html

[H10] 资源自动释放
来源：http://dali.yongpay.top/Article/details/gt2zaznhlzu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhengqikj.top/Article/details/gt2jsamffda.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.guowangkeji.top/Article/details/gt2wvtqrmjx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gt2dzdqgfdn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gt2srbvxjmg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhengqikj.top/Article/details/gt2nwdwffzy.html

Go:   defer f.Close()
来源：http://dali.0kj1m.cn/Article/details/gt2fczpkqwb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cheryme.top/Article/details/gt2jcyszqsi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2qdwwrkkv.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2ynnddiik.html

I. 正则表达式
来源：http://dali.tianlin.xyz/Article/details/gt2ufvtscnh.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2rhbsfnul.html

[I01] 判断是否匹配
来源：http://dali.zhixingplan.top/Article/details/gt2qznwwgza.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.snrcjt.cn/Article/details/gt2dkmoyhux.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cheryme.top/Article/details/gt2hyvopdea.html

JS:   /\d+/.test(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aitzgwlg.html

TS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2dzcsjwaj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.redwolf501.top/Article/details/gt2kxndguac.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yuanzhike.top/Article/details/gt2kjdtaubc.html

Ruby: s.match?(/\d+/)
来源：http://dali.hnxiangtu.top/Article/details/gt2trlltrrs.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2upcbcyle.html

[I02] 提取所有匹配
来源：http://dali.jyoumei.cn/Article/details/gt2vsqyywmo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gt2dbinokcy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ybcxt.top/Article/details/gt2shlvjaeb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangdashe.top/Article/details/gt2cxloqxtp.html

TS:   s.match(/\d+/g)
来源：http://dali.yj20258.top/Article/details/gt2bxtuztzk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cucudq.cn/Article/details/gt2jvoibqvl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gt2oprfpnhe.html

Ruby: s.scan(/\d+/)
来源：http://dali.andypj.xyz/Article/details/gt2skfefmhx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cqqwz.cn/Article/details/gt2fllpjjgy.html

[I03] 提取捕获分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nrfxfzxr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ivvv.top/Article/details/gt2syrflytp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tanke756.top/Article/details/gt2dlckxbbo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tianlin.xyz/Article/details/gt2lnkdxlic.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ppjwa.cn/Article/details/gt2pshaeekg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hysaishi.cn/Article/details/gt2aovovokf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.feifeiyinyue.top/Article/details/gt2rdrvjhgc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nanxuanxn.top/Article/details/gt2shqztdfv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yueranfly.top/Article/details/gt2wxxvyezj.html

[I04] 正则替换
来源：http://dali.jiagoushi.top/Article/details/gt2qgbgjbpk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tianlin.xyz/Article/details/gt2wtiuxjja.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2yssonyde.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xeqehksd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jyoumei.cn/Article/details/gt2lulupwog.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhengqikj.top/Article/details/gt2szshkhjn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sweek.top/Article/details/gt2mixxvoym.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj20258.top/Article/details/gt2xgkfrwto.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2qduafzzw.html

[I05] 按正则拆分
来源：http://dali.zhixingplan.top/Article/details/gt2vaindovg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gaohongyu789.top/Article/details/gt2cfirvvre.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnqzz.top/Article/details/gt2xxrywzpt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjvpynh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gt2hxvqzpig.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2woxektve.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.aizwys.cn/Article/details/gt2acylnfgk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gt2xuwswfzu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cqqwz.cn/Article/details/gt2wfzsqzgz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.wangshuangyany.cn/Article/details/gt2qcclwagv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gt2seovficv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.vqdsnc.cn/Article/details/gt2wbgmavto.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ehwqpu.com/Article/details/gt2mfjhdwtt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zizqegza.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gt2yndnfjvc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenlongwang.top/Article/details/gt2fyytanqm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xziqi.cn/Article/details/gt2jdyayfwo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gt2giotsjsu.html

[I07] 忽略大小写与多行模式
来源：http://dali.xinyue.icu/Article/details/gt2welpenlt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dianchejie.cn/Article/details/gt2fuymkyjv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gt2mrksvgzg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yongpay.top/Article/details/gt2robgxryn.html

TS:   /error/gim
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jeqixeir.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tianlin.xyz/Article/details/gt2ijcjjfxx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmggcss.html

Ruby: s.scan(/error/i)
来源：http://dali.c1oappe.top/Article/details/gt2igqjqaxl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xziqi.cn/Article/details/gt2jneobjoy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jianghu66.top/Article/details/gt2kgclfvvf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinqigfzy.top/Article/details/gt2hhjidmxl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhixingplan.top/Article/details/gt2dsuqdkwf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhixingplan.top/Article/details/gt2jahtbthp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.vqdsnc.cn/Article/details/gt2norahpuc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.redwolf501.top/Article/details/gt2lddwytsx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cdnleiting.top/Article/details/gt2nopqyazk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.andypj.xyz/Article/details/gt2gnpdyurw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gt2zylacpdy.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2mexlcdch.html

J. 日期与时间
来源：http://dali.shangyingyoupin.top/Article/details/gt2jvsmeqep.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2bjlwmpzr.html

[J01] 获取当前时间
来源：http://dali.sweek.top/Article/details/gt2qymwefct.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2phrogyds.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258.top/Article/details/gt2pigktuen.html

JS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gt2rglxzblb.html

TS:   new Date();  Date.now()
来源：http://dali.zhongyouzk.top/Article/details/gt2geuekbkd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.bjfxy.top/Article/details/gt2prgdktgp.html

Go:   time.Now()
来源：http://dali.meibo888.top/Article/details/gt2amjtjybq.html

Ruby: Time.now
来源：http://dali.tian-w.cn/Article/details/gt2gehpvxma.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.0kj1m.cn/Article/details/gt2jcqxipqr.html

[J02] 格式化输出
来源：http://dali.daxiang520.top/Article/details/gt2frnnqtua.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhiwuduotai.top/Article/details/gt2dwrlswpt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gt2eemaenqo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hfpthk.cn/Article/details/gt2ozwqevby.html

TS:   d.toISOString()
来源：http://dali.cdnleiting.top/Article/details/gt2saxawzis.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gt2zdostqfg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xuetiantiany.cn/Article/details/gt2nrckesvt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xylfe.cn/Article/details/gt2mujrvqtz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jlsjyb.cn/Article/details/gt2gnahughn.html

[J03] 字符串解析为日期
来源：http://dali.yj202588.top/Article/details/gt2prswrzqb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aizwys.cn/Article/details/gt2syadrpxt.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tanke756.top/Article/details/gt2smjakvdo.html

JS:   new Date("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gt2dmfldqia.html

TS:   new Date("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gt2dbvqabec.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gt2cbmhuovs.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gt2dkwdnmrg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gt2tkoynjap.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ppjwa.cn/Article/details/gt2gzcduyjz.html

[J04] 时间戳与日期互转
来源：http://dali.ppjwa.cn/Article/details/gt2zuspptzi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fengsongda.top/Article/details/gt2uyoujayr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenlongwang.top/Article/details/gt2onmtewfa.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.kuanghao11.cn/Article/details/gt2fqfhmarv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hammf.cn/Article/details/gt2idbgjgwx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.pycfn.com/Article/details/gt2fsqfvmkz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2nzcielol.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nanxuanxn.top/Article/details/gt2cwcgttgj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.aibaodan.cn/Article/details/gt2nlqrlubm.html

[J05] 时间加减（加 7 天）
来源：http://dali.hongshengwenyu.top/Article/details/gt2xajzgequ.html

Py:   now + timedelta(days=7)
来源：http://dali.xuetiantiany.cn/Article/details/gt2aotcotnc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vrmecnrw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258.top/Article/details/gt2onvijhdz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hysaishi.cn/Article/details/gt2qvtkajft.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.havefunace.top/Article/details/gt2qkvxhwvi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.snrcjt.cn/Article/details/gt2zjvdkoiu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenlongwang.top/Article/details/gt2yunlzrxv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.svipenyu.cn/Article/details/gt2huwqyndy.html

[J06] 计算两时间之差
来源：http://dali.c1oappe.top/Article/details/gt2pzhhulsf.html

Py:   (end - start).total_seconds()
来源：http://dali.xziqi.cn/Article/details/gt2pdydvlfj.html

PHP:  $end->diff($start)->days;
来源：http://dali.sysykeji.top/Article/details/gt2ztllssqx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgfzy.top/Article/details/gt2kppiljnq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fengsongda.top/Article/details/gt2bddxgsii.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenlongwang.top/Article/details/gt2zlophtre.html

Go:   end.Sub(start).Hours()
来源：http://dali.9152youxi.cn/Article/details/gt2dlrmapjz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jqgufenzy.top/Article/details/gt2ctjaykoo.html

C#:   (end - start).TotalSeconds
来源：http://dali.yvedp.cn/Article/details/gt2wdvwrony.html

[J07] 比较两个日期
来源：http://dali.iojbl.cn/Article/details/gt2yanncvps.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gt2nvpmnavf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yvedp.cn/Article/details/gt2agleligg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gt2mcfrmoia.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gt2tvppgtzm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qinopldk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenzaomai.com/Article/details/gt2ivvabrra.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gt2bygqkfjh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fiacoifo.html

[J08] 提取年月日与星期
来源：http://dali.jinqigufen.top/Article/details/gt2zyuivfcn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.kuanghao11.cn/Article/details/gt2ymmsophe.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.bjfxy.top/Article/details/gt2nznlqcfb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qtvrknhe.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xuanzx.com/Article/details/gt2nazjkcxy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnqzz.top/Article/details/gt2ttpqtvoy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj202588.top/Article/details/gt2qbindhcb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sufxvd.cn/Article/details/gt2gfpzexeq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cashguo.top/Article/details/gt2rvjelqqr.html

[J09] 时区处理
来源：http://dali.nanxinkj.top/Article/details/gt2uqvfwjpq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shuidangran.top/Article/details/gt2fdgmdskf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tian-w.cn/Article/details/gt2zijfiqay.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gt2pbqbfvef.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gt2vneldxnj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zwcyiqns.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.pycfn.com/Article/details/gt2fpbhnbwo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ipsxfzie.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yonumen.top/Article/details/gt2ongmzkdr.html

[J10] 取今天 / 本月第一天
来源：http://dali.xylfe.cn/Article/details/gt2vodjegeq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ydzc1.top/Article/details/gt2vylfpsaj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tanke756.top/Article/details/gt2cpuifufg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.pycfn.com/Article/details/gt2wompoigi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2puhnakdh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cdnleiting.top/Article/details/gt2uqlprcfw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhoulong.xyz/Article/details/gt2akufmlmx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnxiangtu.top/Article/details/gt2wqswttrx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.redwolf501.top/Article/details/gt2nqksksbd.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2vjwyqudv.html

K. JSON 与序列化
来源：http://dali.quarkkingdee.top/Article/details/gt2dahnviam.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2eucuuvfr.html

[K01] 对象转 JSON 字符串
来源：http://dali.cucudq.cn/Article/details/gt2lgrogqga.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gt2jgihoemc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cheryme.top/Article/details/gt2cnxkbvrr.html

JS:   JSON.stringify(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2dhixbggq.html

TS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gt2wnzdqlif.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.haohaochexian.top/Article/details/gt2pxnnwedi.html

Go:   json.Marshal(obj)
来源：http://dali.jianghu66.top/Article/details/gt2vfczcedy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ivvv.top/Article/details/gt2musfpesd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2fuzrprlp.html

[K02] JSON 字符串转对象
来源：http://dali.jianghu66.top/Article/details/gt2mjbonozk.html

Py:   json.loads(s)
来源：http://dali.ppjwa.cn/Article/details/gt2iarbvkcw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.birdmap.top/Article/details/gt2dvepuvee.html

JS:   JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gt2rihgsfbd.html

TS:   JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gt2eehlkdql.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sxryk.cn/Article/details/gt2eziyoozk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.pycfn.com/Article/details/gt2byjylkvm.html

Ruby: JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gt2cfqzqakj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pycfn.com/Article/details/gt2rwiielyu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.vqdsnc.cn/Article/details/gt2levxwjjj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gogol.net.cn/Article/details/gt2gplirfgm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gt2mdbuqkiv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dvqqfzvg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gt2lxpfplfk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nwbrower.top/Article/details/gt2xrjpyrwv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jiagoushi.top/Article/details/gt2stiniuff.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.c1oappe.top/Article/details/gt2qkqbhycb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhengqikj.top/Article/details/gt2aslkjjfg.html

[K04] 读取 JSON 文件
来源：http://dali.cashguo.top/Article/details/gt2cjifjnrs.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhixingplan.top/Article/details/gt2owvejwuf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yongpay.top/Article/details/gt2hiqlgpbc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gt2xlbnxmem.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.9152youxi.cn/Article/details/gt2govcjuic.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenzaomai.com/Article/details/gt2xuyhacwu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sysykeji.top/Article/details/gt2btnjcywh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2obwdjynb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gacuekfp.html

[K05] 深拷贝对象
来源：http://dali.cucudq.cn/Article/details/gt2jdisugre.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fcgxsfpi.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhiwuduotai.top/Article/details/gt2zcmyacqk.html

JS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rtsmanog.html

TS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2phpixsin.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xziqi.cn/Article/details/gt2lxhkuesj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gogol.net.cn/Article/details/gt2tbueuhai.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cqqwz.cn/Article/details/gt2lltpdgst.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.feifeiyinyue.top/Article/details/gt2jxdfryfi.html

[K06] 解析 URL 查询串
来源：http://dali.yj202588.top/Article/details/gt2umcxpywu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.fengsongda.top/Article/details/gt2sjlhsdfk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yanxiufei.cn/Article/details/gt2svvqvzns.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gt2alkhvslo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxinkj.top/Article/details/gt2ffctupcq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yueranfly.top/Article/details/gt2wobjossl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2khddekdv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gt2yfpfyepj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gt2fqacwfav.html

[K07] 进制转换
来源：http://dali.hnxiangtu.top/Article/details/gt2bnxbgbyu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2iicnkshz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hfpthk.cn/Article/details/gt2dhvonpqc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2pswdceke.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2njsmwiad.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2uxbigsle.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj20258.top/Article/details/gt2tsajklqv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jianghu66.top/Article/details/gt2qfjfysjs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gt2yhqizdje.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sxeefyrz.html

Py:   pickle.dumps(obj)
来源：http://dali.shuidangran.top/Article/details/gt2vjcwojrk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yongpay.top/Article/details/gt2opsbsrhx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cqqwz.cn/Article/details/gt2fmdjheyd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gt2waahuzcj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nanxinkj.top/Article/details/gt2fauxhwvh.html

Go:   encoding/gob
来源：http://dali.jqgfzy.top/Article/details/gt2brgbezkx.html

Ruby: Marshal.dump(obj)
来源：http://dali.yongpay.top/Article/details/gt2uchswupx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gt2eybhtonc.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2xxmutysh.html

L. 网络请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2siofqjjp.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2mtnsbdea.html

[L01] 发送 GET 请求
来源：http://dali.zhiwuduotai.top/Article/details/gt2mmmbmedg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xuanzx.com/Article/details/gt2esvynjru.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnqzz.top/Article/details/gt2tqlklcvh.html

JS:   await fetch(url)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bbsckxno.html

TS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gt2bayekrjm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shzxlz.cn/Article/details/gt2xbjcwthv.html

Go:   resp, err := http.Get(url)
来源：http://dali.guannengcc.top/Article/details/gt2hzdilxjr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.aibaodan.cn/Article/details/gt2jnppezdi.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sscfuawg.html

[L02] 发送 POST JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zmeekcmh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ehwqpu.com/Article/details/gt2wuykatqf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oeuzkyod.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mgaqoasu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tian-w.cn/Article/details/gt2zvkhrydl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2etuponvs.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zycfv.cn/Article/details/gt2pfikbzoi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yonumen.top/Article/details/gt2hixyimpg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tian-w.cn/Article/details/gt2coplacwk.html

[L03] 设置自定义请求头
来源：http://dali.yj20258.top/Article/details/gt2aovzpsen.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.pengpengdd.cyou/Article/details/gt2zytwjlhl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xinyue.icu/Article/details/gt2axpxzvcd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuanzhike.top/Article/details/gt2odrfaubs.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dashuyun.cn/Article/details/gt2atopgbzz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhongyouzk.top/Article/details/gt2jvwunvxs.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhongyouzk.top/Article/details/gt2evtomaoi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xkbnqibr.html


<!-- 参考信息 -->