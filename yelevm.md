代发 wailian999

Py:   value = d.get("k") or default
来源：http://dali.cashguo.top/Article/details/gt2drkzncnn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.dashuyun.cn/Article/details/gt2lcjzjugw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sysykeji.top/Article/details/gt2efxjjmnn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shuidangran.top/Article/details/gt2nvxhdnqz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cashguo.top/Article/details/gt2qddxoxyz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cheryme.top/Article/details/gt2dnnjjdvo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jlsjyb.cn/Article/details/gt2zjgcnuom.html

C#:   obj?.A?.B ?? default
来源：http://dali.vqdsnc.cn/Article/details/gt2fpandqqa.html

[H07] 断言
来源：http://dali.9152youxi.cn/Article/details/gt2joeejtzb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.quarkkingdee.top/Article/details/gt2zetmwcia.html

PHP:  assert($x > 0);
来源：http://dali.guowangkeji.top/Article/details/gt2qypthfje.html

JS:   console.assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gt2zjquevtg.html

TS:   console.assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gt2jgufxpne.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hywenlv.cn/Article/details/gt2eikfroql.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sysykeji.top/Article/details/gt2jvcnlxbq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hywenlv.cn/Article/details/gt2cjtybyeh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gt2tdyyavoq.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2urecrbpf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sysykeji.top/Article/details/gt2quuakwjs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.iojbl.cn/Article/details/gt2illugows.html

JS:   e.message;  e.stack
来源：http://dali.gzhubu.top/Article/details/gt2lftpnpol.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxuanxn.top/Article/details/gt2lqiqlssb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zdqjudy.top/Article/details/gt2jomhizqm.html

Go:   err.Error()
来源：http://dali.sysykeji.top/Article/details/gt2fiytseht.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhiwuduotai.top/Article/details/gt2inagukmn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gzhubu.top/Article/details/gt2cvuipygt.html

[H09] 带错误码的异常
来源：http://dali.cucudq.cn/Article/details/gt2goldvtsh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.0kj1m.cn/Article/details/gt2gaacefxs.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhongyouzk.top/Article/details/gt2iwasxjfc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigfzy.top/Article/details/gt2cfmerpjg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.mhx1999.top/Article/details/gt2wmfrxmrc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cucudq.cn/Article/details/gt2gsbwulvr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sweek.top/Article/details/gt2lkgiklbc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.kuanghao11.cn/Article/details/gt2jyfcitwg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinqigfzy.top/Article/details/gt2fafjxuyu.html

[H10] 资源自动释放
来源：http://dali.zdqjudy.top/Article/details/gt2hgvstmba.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgufenzy.top/Article/details/gt2hlsapzvi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yvedp.cn/Article/details/gt2knpaoqoo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sufxvd.cn/Article/details/gt2zkpaomnj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gt2gjjbzqrg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhiwuduotai.top/Article/details/gt2jfqkccem.html

Go:   defer f.Close()
来源：http://dali.jqgufenzy.top/Article/details/gt2wtyattea.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daria6918.cn/Article/details/gt2tuklkisb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2bbcuorrg.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2wjmkptio.html

I. 正则表达式
来源：http://dali.ehwqpu.com/Article/details/gt2qjevtscq.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2qxyrutoa.html

[I01] 判断是否匹配
来源：http://dali.0kj1m.cn/Article/details/gt2wvatofte.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinqigufen.top/Article/details/gt2ximablgj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.daxiang520.top/Article/details/gt2fugfdxac.html

JS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gt2qmuectsm.html

TS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gt2ibmwgrnq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gaohongyu789.top/Article/details/gt2glninmid.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.iojbl.cn/Article/details/gt2budgwptj.html

Ruby: s.match?(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gt2hwojgsgz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenlongwang.top/Article/details/gt2anqoaevb.html

[I02] 提取所有匹配
来源：http://dali.iojbl.cn/Article/details/gt2mdwgkhel.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tanke756.top/Article/details/gt2rxfgbivw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hnxiangtu.top/Article/details/gt2ciyagtzs.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xinyue.icu/Article/details/gt2nwfkqvfa.html

TS:   s.match(/\d+/g)
来源：http://dali.meibo888.top/Article/details/gt2hmjeupyr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.smart0.xyz/Article/details/gt2vhkvjlrv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jianghu66.top/Article/details/gt2fuazxyol.html

Ruby: s.scan(/\d+/)
来源：http://dali.mhx1999.top/Article/details/gt2yzwekfpn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ivvv.top/Article/details/gt2upmpovbe.html

[I03] 提取捕获分组
来源：http://dali.gaohongyu789.top/Article/details/gt2vfyaeptv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.havefunace.top/Article/details/gt2egympicj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cucudq.cn/Article/details/gt2yxgxljof.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xylfe.cn/Article/details/gt2mtttsqcr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cashguo.top/Article/details/gt2ydyiblco.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yvedp.cn/Article/details/gt2lvedzkvi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gotoacloud.top/Article/details/gt2utfixvfr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangdashe.top/Article/details/gt2vuiyupmk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gotoacloud.top/Article/details/gt2vjjmuvkf.html

[I04] 正则替换
来源：http://dali.havefunace.top/Article/details/gt2stunnfjh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hnxiangtu.top/Article/details/gt2anghuqcq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tian-w.cn/Article/details/gt2inwuzogv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gt2yjmjcrgm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gt2jciatcck.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gt2mjuoztpp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2vazjukcl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daxiang520.top/Article/details/gt2mdnqneqt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.havefunace.top/Article/details/gt2hjrleuhl.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsxgqsg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hysaishi.cn/Article/details/gt2uufxutei.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2zgfzkxja.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gt2ebiosjiw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gt2owawkvrw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.9152youxi.cn/Article/details/gt2rhhhxpfw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gt2nxlumdqt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wmapzhzd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pycfn.com/Article/details/gt2vojdkxed.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ppjwa.cn/Article/details/gt2yurzpzms.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gt2paemwrkl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yanxiufei.cn/Article/details/gt2ubcbnzqs.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guannengcc.top/Article/details/gt2cjqmsghj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gt2aijsuhcb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gt2kmroblas.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tian-w.cn/Article/details/gt2qpeivlud.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhixingplan.top/Article/details/gt2bdamoecc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gt2njqohodj.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenjidiqi.icu/Article/details/gt2niyefrpp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.mhx1999.top/Article/details/gt2zjfrqbay.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.wangshuangyany.cn/Article/details/gt2cyqykofe.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ydzc1.top/Article/details/gt2iciaxfmp.html

TS:   /error/gim
来源：http://dali.chenjidiqi.icu/Article/details/gt2hkkfdewo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pengpengdd.cyou/Article/details/gt2khukdxmw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zhwajhls.html

Ruby: s.scan(/error/i)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mjmedxtb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yvedp.cn/Article/details/gt2hywunbbn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.mhx1999.top/Article/details/gt2krnmgrqj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.fzhhl.top/Article/details/gt2hhjijilp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.wangshuangyany.cn/Article/details/gt2djaudqnt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.andypj.xyz/Article/details/gt2adcmkakk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gt2zeeywiom.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gotoacloud.top/Article/details/gt2kgagavbc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zhrhyysj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wscgeskm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shangyingyoupin.top/Article/details/gt2wefrqfbg.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2mmibptqi.html

J. 日期与时间
来源：http://dali.yj202588.top/Article/details/gt2rztfzjzs.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2gynuhxfj.html

[J01] 获取当前时间
来源：http://dali.sxryk.cn/Article/details/gt2qaiegqwb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.dashuyun.cn/Article/details/gt2oqomjmtm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gt2lhpmguee.html

JS:   new Date();  Date.now()
来源：http://dali.birdmap.top/Article/details/gt2satsixuw.html

TS:   new Date();  Date.now()
来源：http://dali.ybcxt.top/Article/details/gt2owqzlclg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.guowangkeji.top/Article/details/gt2fluyftpu.html

Go:   time.Now()
来源：http://dali.aibaodan.cn/Article/details/gt2egffkexz.html

Ruby: Time.now
来源：http://dali.316326.xyz/Article/details/gt2mzjqybgh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhoulong.xyz/Article/details/gt2gttcppcd.html

[J02] 格式化输出
来源：http://dali.andypj.xyz/Article/details/gt2paivpcue.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangshuangyany.cn/Article/details/gt2efdeczzl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pycfn.com/Article/details/gt2snkifstp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.meibo888.top/Article/details/gt2xeqiptbx.html

TS:   d.toISOString()
来源：http://dali.vqdsnc.cn/Article/details/gt2gcalphan.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gogol.net.cn/Article/details/gt2xadgqfyo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zdqjudy.top/Article/details/gt2hugezubu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gt2aapobgay.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sysykeji.top/Article/details/gt2vdcgjszu.html

[J03] 字符串解析为日期
来源：http://dali.yj202588.top/Article/details/gt2wtklsoqh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.guowangkeji.top/Article/details/gt2xbdceybt.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.haohaochexian.top/Article/details/gt2fvrondby.html

JS:   new Date("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gt2vawamrsh.html

TS:   new Date("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gt2ilptupab.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uiorrhok.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gt2kopabqay.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2kigcvocb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shzxlz.cn/Article/details/gt2mnijpece.html

[J04] 时间戳与日期互转
来源：http://dali.pycfn.com/Article/details/gt2hegpgxbw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ydzc1.top/Article/details/gt2nefdrjiy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnqzz.top/Article/details/gt2ktzellrh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yueranfly.top/Article/details/gt2rnbhddjy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hysaishi.cn/Article/details/gt2wlnzmxjq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zycfv.cn/Article/details/gt2sdjxlroc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj202588.top/Article/details/gt2dokposlo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenzaomai.com/Article/details/gt2sjjqepbg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sxryk.cn/Article/details/gt2zmdjgqgl.html

[J05] 时间加减（加 7 天）
来源：http://dali.cqqwz.cn/Article/details/gt2mavwuizr.html

Py:   now + timedelta(days=7)
来源：http://dali.smart0.xyz/Article/details/gt2efhwzfrq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.meibo888.top/Article/details/gt2pqabfool.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuanzhike.top/Article/details/gt2amjqnzct.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gt2gjsiivpo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ppjwa.cn/Article/details/gt2zytinjwo.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dashuyun.cn/Article/details/gt2esrufqgr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.feifeiyinyue.top/Article/details/gt2yfyllzeo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guannengcc.top/Article/details/gt2rqvcazux.html

[J06] 计算两时间之差
来源：http://dali.aizwys.cn/Article/details/gt2bqdrcknr.html

Py:   (end - start).total_seconds()
来源：http://dali.aibaodan.cn/Article/details/gt2mxcegmxd.html

PHP:  $end->diff($start)->days;
来源：http://dali.dashuyun.cn/Article/details/gt2rhrnhwaa.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgufenzy.top/Article/details/gt2malvzgpc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shangyingyoupin.top/Article/details/gt2xjfmfwhy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sysykeji.top/Article/details/gt2sizghpyh.html

Go:   end.Sub(start).Hours()
来源：http://dali.yueranfly.top/Article/details/gt2ghemyeoe.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yuxming.cn/Article/details/gt2rlqkxklp.html

C#:   (end - start).TotalSeconds
来源：http://dali.yanxiufei.cn/Article/details/gt2iftxhgzt.html

[J07] 比较两个日期
来源：http://dali.tanke756.top/Article/details/gt2fvmmufuj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gt2agwdoynx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenjidiqi.icu/Article/details/gt2jfowcxir.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ekokyrun.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hfpthk.cn/Article/details/gt2edbtkali.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.wangdashe.top/Article/details/gt2hljkemru.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yongpay.top/Article/details/gt2rsmyjdma.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gt2wbflqnbc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gt2aixzpegb.html

[J08] 提取年月日与星期
来源：http://dali.cashguo.top/Article/details/gt2qgjemllt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nanxinkj.top/Article/details/gt2cdvopmvz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.316326.xyz/Article/details/gt2piblaehp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tian-w.cn/Article/details/gt2bjzidnfj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhoulong.xyz/Article/details/gt2corujuho.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.kuanghao11.cn/Article/details/gt2eeyxudnr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.iojbl.cn/Article/details/gt2tpljpspy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cheryme.top/Article/details/gt2jdpkoibk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhongyouzk.top/Article/details/gt2wbpfydvw.html

[J09] 时区处理
来源：http://dali.zdqjudy.top/Article/details/gt2sxojpxtg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.iojbl.cn/Article/details/gt2wrphqdxd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj20258.top/Article/details/gt2jbbqayqd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhiwuduotai.top/Article/details/gt2aqpkmfek.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigufen.top/Article/details/gt2rrpvlxwv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.quarkkingdee.top/Article/details/gt2cforjycs.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hfpthk.cn/Article/details/gt2jwvtgwcc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangdashe.top/Article/details/gt2jnwlspym.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.quarkkingdee.top/Article/details/gt2xwevmtvz.html

[J10] 取今天 / 本月第一天
来源：http://dali.hammf.cn/Article/details/gt2xefhbimu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cashguo.top/Article/details/gt2qbgdkesv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhongyouzk.top/Article/details/gt2bbqdnghp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nwbrower.top/Article/details/gt2pubbxtmd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nwbrower.top/Article/details/gt2pufbjqrw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dashuyun.cn/Article/details/gt2zqrohlgx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pycfn.com/Article/details/gt2ojnyvdxd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2efmzlzhf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ydzc1.top/Article/details/gt2xfyilssf.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2acgexkpi.html

K. JSON 与序列化
来源：http://dali.pengpengdd.cyou/Article/details/gt2fjdvusqt.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2efmsprqo.html

[K01] 对象转 JSON 字符串
来源：http://dali.yueranfly.top/Article/details/gt2fijqfrqr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gt2mphywbdo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenjidiqi.icu/Article/details/gt2wuwdpmmc.html

JS:   JSON.stringify(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2wpyyznvt.html

TS:   JSON.stringify(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pkhexkcj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.wangshuangyany.cn/Article/details/gt2epebxsxz.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnjqalq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.316326.xyz/Article/details/gt2uvudhwlx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2hlhexurx.html

[K02] JSON 字符串转对象
来源：http://dali.fengsongda.top/Article/details/gt2oztavpzg.html

Py:   json.loads(s)
来源：http://dali.tian-w.cn/Article/details/gt2pvvxajua.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shzxlz.cn/Article/details/gt2xdnmudxr.html

JS:   JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gt2cnbyfagb.html

TS:   JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gt2dumyvaev.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhengqikj.top/Article/details/gt2eypdmvhb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nfwxrqcp.html

Ruby: JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gt2zccjggpd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2vzeasxcg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.guannengcc.top/Article/details/gt2wwesztpz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gt2ftfhnjtg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hnxiangtu.top/Article/details/gt2jozaobbx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gt2jbbevlye.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.andypj.xyz/Article/details/gt2ipdknkzm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2hxoaqbnq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hongshengwenyu.top/Article/details/gt2mmhdomzi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj20258888.top/Article/details/gt2oektpigy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shzxlz.cn/Article/details/gt2hwbmykhk.html

[K04] 读取 JSON 文件
来源：http://dali.chenzaomai.com/Article/details/gt2gvabqycy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.daria6918.cn/Article/details/gt2rdvquqhv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.pengpengdd.cyou/Article/details/gt2hrnmkyix.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nlgcyjks.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnxiangtu.top/Article/details/gt2gwxzrvyq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vhxeymhy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gt2dedsavnw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jqgufenzy.top/Article/details/gt2qaukjnya.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.redwolf501.top/Article/details/gt2cigkiieg.html

[K05] 深拷贝对象
来源：http://dali.ppjwa.cn/Article/details/gt2berebfwj.html

Py:   copy.deepcopy(obj)
来源：http://dali.meibo888.top/Article/details/gt2wuhghaek.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hnxiangtu.top/Article/details/gt2cgbxpbnw.html

JS:   structuredClone(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qrnrrymq.html

TS:   structuredClone(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2xzzlpcwl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.guannengcc.top/Article/details/gt2vcggurxb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.bjfxy.top/Article/details/gt2vyxdjwmw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuanzx.com/Article/details/gt2jewgextx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oiyfmyxl.html

[K06] 解析 URL 查询串
来源：http://dali.shzxlz.cn/Article/details/gt2qsjgkzsa.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.birdmap.top/Article/details/gt2xursevdw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tanke756.top/Article/details/gt2ynsvoqek.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gt2cecijtha.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.iojbl.cn/Article/details/gt2avmhpbxb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.guowangkeji.top/Article/details/gt2lmssunit.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gt2teztxttw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gt2qdooromm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gt2wbviqvkn.html

[K07] 进制转换
来源：http://dali.0kj1m.cn/Article/details/gt2ynwmlies.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2otzarwhw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jianghu66.top/Article/details/gt2rmyzegxt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gt2orzmbhdn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gt2kinlmurz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gt2lcjdgela.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.snrcjt.cn/Article/details/gt2kmwlhsae.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shuidangran.top/Article/details/gt2mczhkqln.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2jugyirro.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnxplzs.html

Py:   pickle.dumps(obj)
来源：http://dali.yonumen.top/Article/details/gt2tcohovty.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jqgfzy.top/Article/details/gt2nwspxgnv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gt2osqzcxhw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zdqjudy.top/Article/details/gt2tdekqvbr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.smart0.xyz/Article/details/gt2doslqgli.html

Go:   encoding/gob
来源：http://dali.ydzc1.top/Article/details/gt2okminvqu.html

Ruby: Marshal.dump(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2jndvxfji.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gt2edefuhnq.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pihgcfet.html

L. 网络请求
来源：http://dali.sxryk.cn/Article/details/gt2otxdpfao.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gsputwix.html

[L01] 发送 GET 请求
来源：http://dali.redwolf501.top/Article/details/gt2ckrymqhh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gaohongyu789.top/Article/details/gt2likrflnz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jyoumei.cn/Article/details/gt2uopyhhhd.html

JS:   await fetch(url)
来源：http://dali.hongshengwenyu.top/Article/details/gt2snkvhkyv.html

TS:   await fetch(url)
来源：http://dali.yonumen.top/Article/details/gt2kdsvwnfz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj20258888.top/Article/details/gt2cdznzebw.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ecrnwwxj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ppjwa.cn/Article/details/gt2hxcqkjxb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tanke756.top/Article/details/gt2mckelknk.html

[L02] 发送 POST JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qoapwdlt.html


<!-- 参考信息 -->