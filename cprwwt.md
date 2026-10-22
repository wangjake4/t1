代发 wailian999

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jyoumei.cn/Article/details/gt2lbetpcuc.html

Ruby: rescue ArgumentError => e
来源：http://dali.xziqi.cn/Article/details/gt2bebysvoq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangdashe.top/Article/details/gt2ijfiwrbm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhixingplan.top/Article/details/gt2ukkuaqlg.html

Py:   value = d.get("k") or default
来源：http://dali.yanxiufei.cn/Article/details/gt2vikwklws.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2loylokhb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ybcxt.top/Article/details/gt2yamgtfhq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigufen.top/Article/details/gt2gsemtqom.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhongyouzk.top/Article/details/gt2gdscubcj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xziqi.cn/Article/details/gt2ipgdlxyf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jlsjyb.cn/Article/details/gt2nejlsqej.html

C#:   obj?.A?.B ?? default
来源：http://dali.gzhubu.top/Article/details/gt2vsydltei.html

[H07] 断言
来源：http://dali.zdqjudy.top/Article/details/gt2wxplazsn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hongshengwenyu.top/Article/details/gt2owwkrzpj.html

PHP:  assert($x > 0);
来源：http://dali.guowangkeji.top/Article/details/gt2xiyipbmq.html

JS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gt2dtkdxcly.html

TS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gt2xsyxcvol.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nwbrower.top/Article/details/gt2wazbvhpo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.andypj.xyz/Article/details/gt2nnuoucky.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.mhx1999.top/Article/details/gt2uoubiksk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gt2imelpyuk.html

[H08] 获取错误信息与堆栈
来源：http://dali.fengsongda.top/Article/details/gt2pqqokcan.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.daria6918.cn/Article/details/gt2csydaldk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yangfankeji.com/Article/details/gt2ifsvmxhf.html

JS:   e.message;  e.stack
来源：http://dali.aizwys.cn/Article/details/gt2kgspjxit.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xinyue.icu/Article/details/gt2ivhgwokl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ehwqpu.com/Article/details/gt2xgpuobvq.html

Go:   err.Error()
来源：http://dali.yj20258.top/Article/details/gt2mijqymhh.html

Ruby: e.message;  e.backtrace
来源：http://dali.jlsjyb.cn/Article/details/gt2yoruytuu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yuanzhike.top/Article/details/gt2zfvamxoa.html

[H09] 带错误码的异常
来源：http://dali.jinqigufen.top/Article/details/gt2epzcolom.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gogol.net.cn/Article/details/gt2ypxrozge.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sysykeji.top/Article/details/gt2oerfghua.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cucudq.cn/Article/details/gt2jvcnnvmp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2slfdbbeg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ngmuiajt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zdqjudy.top/Article/details/gt2feghfzxm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jianghu66.top/Article/details/gt2neotvwbc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.kuanghao11.cn/Article/details/gt2gcwazwzs.html

[H10] 资源自动释放
来源：http://dali.guannengcc.top/Article/details/gt2oojinidw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xylfe.cn/Article/details/gt2yprnkpfu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ybcxt.top/Article/details/gt2ygdnbqbc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jianghu66.top/Article/details/gt2fylthqjs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cashguo.top/Article/details/gt2ahdkscvx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.iojbl.cn/Article/details/gt2mzuilpbv.html

Go:   defer f.Close()
来源：http://dali.kuanghao11.cn/Article/details/gt2drufcubs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.quarkkingdee.top/Article/details/gt2njsrkrar.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2mdorbamn.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2jpzwilit.html

I. 正则表达式
来源：http://dali.jinqigfzy.top/Article/details/gt2drkhkcms.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2zilrzzwh.html

[I01] 判断是否匹配
来源：http://dali.sysykeji.top/Article/details/gt2ungchlly.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hzaspuar.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdprgdr.html

JS:   /\d+/.test(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qhojexlk.html

TS:   /\d+/.test(s)
来源：http://dali.redwolf501.top/Article/details/gt2fthehzxu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ydzc1.top/Article/details/gt2giuywlpy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gogol.net.cn/Article/details/gt2ycqcdgyg.html

Ruby: s.match?(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gt2udozvqnc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnqzz.top/Article/details/gt2cbxefisc.html

[I02] 提取所有匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rzysgzdq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gt2sackgtdb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xylfe.cn/Article/details/gt2oigchdut.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xziqi.cn/Article/details/gt2ojmejskv.html

TS:   s.match(/\d+/g)
来源：http://dali.daria6918.cn/Article/details/gt2gqcenlfb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2upkeojtz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tian-w.cn/Article/details/gt2cgwnfgis.html

Ruby: s.scan(/\d+/)
来源：http://dali.fengsongda.top/Article/details/gt2quliehds.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zycfv.cn/Article/details/gt2mugiaotk.html

[I03] 提取捕获分组
来源：http://dali.dashuyun.cn/Article/details/gt2vhxeeitk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj202588.top/Article/details/gt2yewninge.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cucudq.cn/Article/details/gt2hzfszvmd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.dashuyun.cn/Article/details/gt2zmezyjph.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jianghu66.top/Article/details/gt2gdvsyadf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.316326.xyz/Article/details/gt2zbgbrbtj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.c1oappe.top/Article/details/gt2sdvqqwry.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhoulong.xyz/Article/details/gt2vzkzjxak.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hnenesrk.html

[I04] 正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wehiggzg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.vqdsnc.cn/Article/details/gt2fsdlicus.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shzxlz.cn/Article/details/gt2ecckleku.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wfwzjqmk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2rolwglln.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.meibo888.top/Article/details/gt2kfdjtxgd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2itmyyrwg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.aizwys.cn/Article/details/gt2knzftbwf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jyoumei.cn/Article/details/gt2xhxfqowo.html

[I05] 按正则拆分
来源：http://dali.hnqzz.top/Article/details/gt2ftmshzav.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daxiang520.top/Article/details/gt2okbhjkoh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2dgocttzd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gt2cmeabiko.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gt2dfnafzxe.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhiwuduotai.top/Article/details/gt2xagnowrh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj202588.top/Article/details/gt2ltpqgypj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gt2axsarohq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xziqi.cn/Article/details/gt2fiofnbgm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2axukckao.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkelzij.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.vqdsnc.cn/Article/details/gt2gpewujew.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sweek.top/Article/details/gt2hutjaqgs.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gt2scsaekaq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gt2bzvfaewl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gzhubu.top/Article/details/gt2cwsgmkym.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yangfankeji.com/Article/details/gt2bejckice.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gt2ptksrbkj.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rciizwou.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yueranfly.top/Article/details/gt2zloasxfs.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.smart0.xyz/Article/details/gt2uubczevc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhiwuduotai.top/Article/details/gt2bqajaohe.html

TS:   /error/gim
来源：http://dali.yvedp.cn/Article/details/gt2vsehtjam.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.redwolf501.top/Article/details/gt2eicgcriw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cheryme.top/Article/details/gt2daorffdq.html

Ruby: s.scan(/error/i)
来源：http://dali.cashguo.top/Article/details/gt2ssddcsry.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xylfe.cn/Article/details/gt2qupquldr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.snrcjt.cn/Article/details/gt2skxjolxy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhongyouzk.top/Article/details/gt2fccxosdr.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.316326.xyz/Article/details/gt2fhfxlbjt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jlyabewi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnqzz.top/Article/details/gt2lgbftjkz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenjidiqi.icu/Article/details/gt2jhomwbgh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yuxming.cn/Article/details/gt2fiaforvq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gogol.net.cn/Article/details/gt2joxyaymd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.pengpengdd.cyou/Article/details/gt2jyflltyi.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2qdpgrdlk.html

J. 日期与时间
来源：http://dali.jqgfzy.top/Article/details/gt2yadymtxo.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2qhfvxnxx.html

[J01] 获取当前时间
来源：http://dali.316326.xyz/Article/details/gt2rqqknlso.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhixingplan.top/Article/details/gt2ujavmmjg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuxming.cn/Article/details/gt2zchrdmuq.html

JS:   new Date();  Date.now()
来源：http://dali.chenlongwang.top/Article/details/gt2euuvwvla.html

TS:   new Date();  Date.now()
来源：http://dali.nanxuanxn.top/Article/details/gt2pgifvyrd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.daria6918.cn/Article/details/gt2xkauzeft.html

Go:   time.Now()
来源：http://dali.ehwqpu.com/Article/details/gt2ihipgrqj.html

Ruby: Time.now
来源：http://dali.sysykeji.top/Article/details/gt2vzadptyi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cheryme.top/Article/details/gt2ekrppmcc.html

[J02] 格式化输出
来源：http://dali.fzhhl.top/Article/details/gt2oqjemkvt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xziqi.cn/Article/details/gt2mymmmjmh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gt2jjwmopaa.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yuxming.cn/Article/details/gt2wzonqzer.html

TS:   d.toISOString()
来源：http://dali.yvedp.cn/Article/details/gt2pgmfyexf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zycfv.cn/Article/details/gt2mcmswpvp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jlsjyb.cn/Article/details/gt2raytyxkz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2amtiyhig.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gotoacloud.top/Article/details/gt2bsoyvbeq.html

[J03] 字符串解析为日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fkfwccmj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.dianchejie.cn/Article/details/gt2bakirkjk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shuidangran.top/Article/details/gt2igzndkmj.html

JS:   new Date("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gt2ogisdzvi.html

TS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lxfxgdgb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gt2gaunimag.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gt2ztrejkur.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gt2vdrgfdjp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cheryme.top/Article/details/gt2uqhhizqw.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258888.top/Article/details/gt2hgvozxks.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xziqi.cn/Article/details/gt2spuqymyn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangshuangyany.cn/Article/details/gt2eckdwzxy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dgshuusa.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sufxvd.cn/Article/details/gt2rmydpinl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhongyouzk.top/Article/details/gt2osdjmcmu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fzhhl.top/Article/details/gt2xaunzcqe.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xuanzx.com/Article/details/gt2qzrsfrlo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinqigfzy.top/Article/details/gt2eywdaxxr.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhoulong.xyz/Article/details/gt2dztmoscx.html

Py:   now + timedelta(days=7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kocivqmz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.aizwys.cn/Article/details/gt2neoyuhuu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.havefunace.top/Article/details/gt2nouoghdr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gt2imfkxqpn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shuidangran.top/Article/details/gt2jpnswsfp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ztrxocrw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.redwolf501.top/Article/details/gt2pksscsda.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shzxlz.cn/Article/details/gt2afocoaak.html

[J06] 计算两时间之差
来源：http://dali.kuanghao11.cn/Article/details/gt2hephqfwr.html

Py:   (end - start).total_seconds()
来源：http://dali.yvedp.cn/Article/details/gt2bblxcbim.html

PHP:  $end->diff($start)->days;
来源：http://dali.gotoacloud.top/Article/details/gt2hbvetxnw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.fzhhl.top/Article/details/gt2evzhtkrj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xylfe.cn/Article/details/gt2icucftzf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yangfankeji.com/Article/details/gt2rphvecsx.html

Go:   end.Sub(start).Hours()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dwqanzdj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.havefunace.top/Article/details/gt2xmqupbgk.html

C#:   (end - start).TotalSeconds
来源：http://dali.bjfxy.top/Article/details/gt2uqbjiirb.html

[J07] 比较两个日期
来源：http://dali.wangshuangyany.cn/Article/details/gt2zfkbqmuv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gt2hxmognwl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnqzz.top/Article/details/gt2fxpvjana.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gt2jkyjmfjj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigufen.top/Article/details/gt2naqovgjn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gogol.net.cn/Article/details/gt2rkufnzxk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cdnleiting.top/Article/details/gt2ymalnivv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gt2bgonlijt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gt2qdievisn.html

[J08] 提取年月日与星期
来源：http://dali.zdqjudy.top/Article/details/gt2emklhbsc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jyoumei.cn/Article/details/gt2kxbgmikp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.daria6918.cn/Article/details/gt2oeyhujuv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.0kj1m.cn/Article/details/gt2rciuhnrr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shangyingyoupin.top/Article/details/gt2gqxkzybz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhoulong.xyz/Article/details/gt2ueqvohll.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.nanxinkj.top/Article/details/gt2gwmyswnp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jlsjyb.cn/Article/details/gt2gqfdoszj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jlsjyb.cn/Article/details/gt2fthfgdke.html

[J09] 时区处理
来源：http://dali.guowangkeji.top/Article/details/gt2weczbzdk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.andypj.xyz/Article/details/gt2qwzieeyp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenjidiqi.icu/Article/details/gt2cdienmzo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gt2ovvuqsuv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iqxpoumq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.havefunace.top/Article/details/gt2akfeqpmg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhengqikj.top/Article/details/gt2qlydwxcl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cdnleiting.top/Article/details/gt2uiswmkok.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.bjfxy.top/Article/details/gt2kwpwvexx.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj20258888.top/Article/details/gt2dceghwut.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kkwtphcb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxinkj.top/Article/details/gt2mxbvqxuw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ydzc1.top/Article/details/gt2aqjdfzdi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.mhx1999.top/Article/details/gt2bamzovgx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.pycfn.com/Article/details/gt2scjwatse.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jlsjyb.cn/Article/details/gt2avcgigfw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ehwqpu.com/Article/details/gt2ekofyuiw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shzxlz.cn/Article/details/gt2culzhdbu.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2jkrclnwp.html

K. JSON 与序列化
来源：http://dali.hnxiangtu.top/Article/details/gt2ekvodkqn.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qdfbtxbg.html

[K01] 对象转 JSON 字符串
来源：http://dali.gzhubu.top/Article/details/gt2dyghqjgx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gogol.net.cn/Article/details/gt2edoctxob.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.guannengcc.top/Article/details/gt2cyyufwkc.html

JS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gt2rncrnujn.html

TS:   JSON.stringify(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2cudvxznt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jqgfzy.top/Article/details/gt2goxfgktp.html

Go:   json.Marshal(obj)
来源：http://dali.nwbrower.top/Article/details/gt2dxlyezap.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ybcxt.top/Article/details/gt2svicdjzg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.wangdashe.top/Article/details/gt2mphxcteb.html

[K02] JSON 字符串转对象
来源：http://dali.shangyingyoupin.top/Article/details/gt2kkdaqvds.html

Py:   json.loads(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bantadaw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.dianchejie.cn/Article/details/gt2ukipxzxb.html

JS:   JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gt2tiuuqlsk.html

TS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gt2hjoqyrdb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tanke756.top/Article/details/gt2zhghfpfn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.birdmap.top/Article/details/gt2coswxisg.html

Ruby: JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2rixfjoie.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shuidangran.top/Article/details/gt2aoyugtew.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.smart0.xyz/Article/details/gt2tenmmcmj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jywdcncs.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yongpay.top/Article/details/gt2lwkxxnfa.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zsjwtuqw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.dashuyun.cn/Article/details/gt2vhtqabap.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xinyue.icu/Article/details/gt2gbuhsvey.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqlrndf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hammf.cn/Article/details/gt2rbydcjmn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258888.top/Article/details/gt2ezosjojd.html

[K04] 读取 JSON 文件
来源：http://dali.gzhubu.top/Article/details/gt2uubrocaz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kccgyqjt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gzhubu.top/Article/details/gt2qskkwmml.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cqqwz.cn/Article/details/gt2nipwtpho.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xziqi.cn/Article/details/gt2vydkoizo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guowangkeji.top/Article/details/gt2ijcdknwg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhixingplan.top/Article/details/gt2kgjygumo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gt2niuvlotw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xuanzx.com/Article/details/gt2myodgdlw.html

[K05] 深拷贝对象
来源：http://dali.zhixingplan.top/Article/details/gt2mcmksrwm.html

Py:   copy.deepcopy(obj)
来源：http://dali.ivvv.top/Article/details/gt2mccatxjg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nanxinkj.top/Article/details/gt2opwbjiyt.html

JS:   structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2ygdmvoyr.html

TS:   structuredClone(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2aevlcrbs.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xuanzx.com/Article/details/gt2wpwjhosk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vwtrttjb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ehwqpu.com/Article/details/gt2flndsogr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ehwqpu.com/Article/details/gt2adlvfavt.html

[K06] 解析 URL 查询串
来源：http://dali.yj202588.top/Article/details/gt2akquckht.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tebbwmlv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenzaomai.com/Article/details/gt2ngabcwrn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuanzhike.top/Article/details/gt2wevxvxuo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.smart0.xyz/Article/details/gt2wzsylacx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.iojbl.cn/Article/details/gt2esoboruy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gt2zusucnut.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gt2vxuwtawz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gt2bwaydkhd.html

[K07] 进制转换
来源：http://dali.haohaochexian.top/Article/details/gt2ojaaavld.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gt2dveeopau.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.aibaodan.cn/Article/details/gt2kdspfejh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2dgzbteer.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gt2tfrivynt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vmlxoqke.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ppjwa.cn/Article/details/gt2knnmfpdn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xuetiantiany.cn/Article/details/gt2umzxxorz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.birdmap.top/Article/details/gt2sbvvsyuw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hysaishi.cn/Article/details/gt2xmeotzeu.html

Py:   pickle.dumps(obj)
来源：http://dali.havefunace.top/Article/details/gt2vtezopny.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2wbgsixbz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.meibo888.top/Article/details/gt2gfwrvbly.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenzaomai.com/Article/details/gt2vrikrnoq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cdnleiting.top/Article/details/gt2mzbjpfpp.html

Go:   encoding/gob
来源：http://dali.zhiwuduotai.top/Article/details/gt2lulojgif.html

Ruby: Marshal.dump(obj)
来源：http://dali.sysykeji.top/Article/details/gt2qsbnyoik.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gt2rkzcvmda.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2loqedmmm.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2osooqquk.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2vhxjcold.html

[L01] 发送 GET 请求
来源：http://dali.mhx1999.top/Article/details/gt2udrvporh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.havefunace.top/Article/details/gt2whctgkja.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xuetiantiany.cn/Article/details/gt2lvgvlmdj.html

JS:   await fetch(url)
来源：http://dali.svipenyu.cn/Article/details/gt2yoyzrtog.html

TS:   await fetch(url)
来源：http://dali.chenlongwang.top/Article/details/gt2oalujjpi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.dianchejie.cn/Article/details/gt2olxjgsql.html


<!-- 参考信息 -->