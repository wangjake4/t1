代发 wailian999

[H07] 断言
来源：http://dali.daxiang520.top/Article/details/gt2ejnwlwst.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenjidiqi.icu/Article/details/gt2noclbgej.html

PHP:  assert($x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2elldwfej.html

JS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2wkgtontn.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmghfqgr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.daria6918.cn/Article/details/gt2ecrdsimz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.bjfxy.top/Article/details/gt2udwvdptu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cqqwz.cn/Article/details/gt2hpwjpthf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gt2swmrfxmh.html

[H08] 获取错误信息与堆栈
来源：http://dali.redwolf501.top/Article/details/gt2hjffxjgm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.fzhhl.top/Article/details/gt2fnpsolth.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cheryme.top/Article/details/gt2cstpkgvn.html

JS:   e.message;  e.stack
来源：http://dali.zycfv.cn/Article/details/gt2jbfywhqz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenlongwang.top/Article/details/gt2ziutkvmw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ivvv.top/Article/details/gt2cqkufesz.html

Go:   err.Error()
来源：http://dali.chenlongwang.top/Article/details/gt2wvzcbqhu.html

Ruby: e.message;  e.backtrace
来源：http://dali.smart0.xyz/Article/details/gt2yekagqrb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hywenlv.cn/Article/details/gt2oapigqqq.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qwpwxwgt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.svipenyu.cn/Article/details/gt2cmisqpkp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhengqikj.top/Article/details/gt2vyzvwlur.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.andypj.xyz/Article/details/gt2blluehne.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cheryme.top/Article/details/gt2dsbbzoad.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trggyaeo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.kuanghao11.cn/Article/details/gt2pbkylgcu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cqqwz.cn/Article/details/gt2jeqsdoue.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhongyouzk.top/Article/details/gt2xqbtxlrk.html

[H10] 资源自动释放
来源：http://dali.pengpengdd.cyou/Article/details/gt2zovtzhiz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hysaishi.cn/Article/details/gt2wqwxsloa.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yueranfly.top/Article/details/gt2hopaqyto.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.316326.xyz/Article/details/gt2cvyytipn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgufenzy.top/Article/details/gt2jypefatf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yuxming.cn/Article/details/gt2kkcvttes.html

Go:   defer f.Close()
来源：http://dali.chenzaomai.com/Article/details/gt2fcqzoysq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daria6918.cn/Article/details/gt2ofcckzyh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2ptalgumm.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2fgzrjrni.html

I. 正则表达式
来源：http://dali.cucudq.cn/Article/details/gt2gynakiob.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2gwnnkpah.html

[I01] 判断是否匹配
来源：http://dali.snrcjt.cn/Article/details/gt2mlmlmbje.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ydzc1.top/Article/details/gt2mbeoqjlw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhixingplan.top/Article/details/gt2iuprpbaf.html

JS:   /\d+/.test(s)
来源：http://dali.yuxming.cn/Article/details/gt2yshxpiwy.html

TS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2ifbypcjb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gtccwluu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fzhhl.top/Article/details/gt2qgsmorun.html

Ruby: s.match?(/\d+/)
来源：http://dali.sweek.top/Article/details/gt2nwfuycfw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cucudq.cn/Article/details/gt2ojecosem.html

[I02] 提取所有匹配
来源：http://dali.0kj1m.cn/Article/details/gt2kgtfojgb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aecdfgur.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhiwuduotai.top/Article/details/gt2lejdexwy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenlongwang.top/Article/details/gt2yewgikvg.html

TS:   s.match(/\d+/g)
来源：http://dali.zhengqikj.top/Article/details/gt2vlluboej.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hfpthk.cn/Article/details/gt2lwsmgxff.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.fengsongda.top/Article/details/gt2axdeunma.html

Ruby: s.scan(/\d+/)
来源：http://dali.yangfankeji.com/Article/details/gt2kqrfcbfu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yonumen.top/Article/details/gt2krlifpgd.html

[I03] 提取捕获分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ccnborvr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kbbiiccc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hammf.cn/Article/details/gt2haqpoxuc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tanke756.top/Article/details/gt2fmsdputr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhengqikj.top/Article/details/gt2lbfsxpji.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cucudq.cn/Article/details/gt2ckwtzfgh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zycfv.cn/Article/details/gt2ycasldlg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cucudq.cn/Article/details/gt2fbdkpydm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinqigfzy.top/Article/details/gt2opddlyhc.html

[I04] 正则替换
来源：http://dali.andypj.xyz/Article/details/gt2aayrzymh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.havefunace.top/Article/details/gt2noqyjpjh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258888.top/Article/details/gt2yksnvqje.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yvedp.cn/Article/details/gt2zixehzqr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gt2mhcpwuit.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xinyue.icu/Article/details/gt2ciumpkqr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yvedp.cn/Article/details/gt2kothrhvk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yanxiufei.cn/Article/details/gt2wmqecfau.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gt2eqvrgbvu.html

[I05] 按正则拆分
来源：http://dali.cashguo.top/Article/details/gt2bycacnkt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yongpay.top/Article/details/gt2vqjhbthv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.iojbl.cn/Article/details/gt2bevvxlva.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gt2ovvtizbr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gt2fhjsrsfa.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinqigufen.top/Article/details/gt2qzktbark.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gt2vdrnlgez.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2difjbhpx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aibaodan.cn/Article/details/gt2mwrblefk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ybcxt.top/Article/details/gt2aleyslsf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gt2ogneahgl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenlongwang.top/Article/details/gt2axvpgxzt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgfzy.top/Article/details/gt2anguzbgz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gt2wkvnpcgh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gt2etzumcxn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gogol.net.cn/Article/details/gt2doukofad.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinqigufen.top/Article/details/gt2ovfiawnm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gt2cellpwnv.html

[I07] 忽略大小写与多行模式
来源：http://dali.hysaishi.cn/Article/details/gt2vkfweupa.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sweek.top/Article/details/gt2nkksrryb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gt2wekrnshl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258888.top/Article/details/gt2pjdvhlez.html

TS:   /error/gim
来源：http://dali.yongpay.top/Article/details/gt2pnrybacu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pxdszwoo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ggbnftji.html

Ruby: s.scan(/error/i)
来源：http://dali.gotoacloud.top/Article/details/gt2ehpkpxgd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.daxiang520.top/Article/details/gt2ubhsvglt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.aibaodan.cn/Article/details/gt2uajtlvbm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhixingplan.top/Article/details/gt2ueqnalon.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sdznklfe.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xnbyudyp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2glhplgtu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.guannengcc.top/Article/details/gt2wyrqpnyf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xinyue.icu/Article/details/gt2xmwfnqgi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tianlin.xyz/Article/details/gt2eimxlrpj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.meibo888.top/Article/details/gt2opcthern.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2unoutjoo.html

J. 日期与时间
来源：http://dali.cheryme.top/Article/details/gt2pwldqksf.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2pgakgpfl.html

[J01] 获取当前时间
来源：http://dali.haohaochexian.top/Article/details/gt2ywseuseo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.aibaodan.cn/Article/details/gt2deijwbjt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gt2hfswkojo.html

JS:   new Date();  Date.now()
来源：http://dali.svipenyu.cn/Article/details/gt2rdcaxldm.html

TS:   new Date();  Date.now()
来源：http://dali.c1oappe.top/Article/details/gt2izcwjggh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.mhx1999.top/Article/details/gt2uzutwuov.html

Go:   time.Now()
来源：http://dali.yangfankeji.com/Article/details/gt2hexnosct.html

Ruby: Time.now
来源：http://dali.yonumen.top/Article/details/gt2chrxhflu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tianlin.xyz/Article/details/gt2gwhxpjyq.html

[J02] 格式化输出
来源：http://dali.c1oappe.top/Article/details/gt2ddxywtha.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jianghu66.top/Article/details/gt2bzyyjmyx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cdnleiting.top/Article/details/gt2ewpwgcju.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yangfankeji.com/Article/details/gt2agixbmxa.html

TS:   d.toISOString()
来源：http://dali.yuxming.cn/Article/details/gt2wpxpzzwb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gogol.net.cn/Article/details/gt2szkoebmr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daxiang520.top/Article/details/gt2chskiuhl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gt2mwzjrrvl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hammf.cn/Article/details/gt2upsmncwa.html

[J03] 字符串解析为日期
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cjlylavs.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhengqikj.top/Article/details/gt2dhocpsbx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ydzc1.top/Article/details/gt2kcpmcaxj.html

JS:   new Date("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ruktubkg.html

TS:   new Date("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2wdydlsbb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gt2nhcjkjle.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gt2iaavfwiw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gt2quggxejz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jyoumei.cn/Article/details/gt2xyqnnuvi.html

[J04] 时间戳与日期互转
来源：http://dali.dianchejie.cn/Article/details/gt2gczqncgm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sufxvd.cn/Article/details/gt2ojrfmngq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.0kj1m.cn/Article/details/gt2puipubmo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daria6918.cn/Article/details/gt2jlpmtmmr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ybcxt.top/Article/details/gt2mqdwzklj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.daxiang520.top/Article/details/gt2pkwnftpf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cheryme.top/Article/details/gt2hasndsgp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gt2phjfsuyq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yueranfly.top/Article/details/gt2swpjihmb.html

[J05] 时间加减（加 7 天）
来源：http://dali.birdmap.top/Article/details/gt2urdkodtv.html

Py:   now + timedelta(days=7)
来源：http://dali.snrcjt.cn/Article/details/gt2jketwmfc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.quarkkingdee.top/Article/details/gt2kgzynnmt.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gt2gozqbdcv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hysaishi.cn/Article/details/gt2mlurzdas.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gotoacloud.top/Article/details/gt2qaoclrtn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cucudq.cn/Article/details/gt2atgjqhdl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlolvyj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinqigfzy.top/Article/details/gt2mqcdfvqi.html

[J06] 计算两时间之差
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bdvmevsn.html

Py:   (end - start).total_seconds()
来源：http://dali.cqqwz.cn/Article/details/gt2kdtnklgz.html

PHP:  $end->diff($start)->days;
来源：http://dali.sufxvd.cn/Article/details/gt2lgylgxzs.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daxiang520.top/Article/details/gt2kakpaall.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cashguo.top/Article/details/gt2pacjrboh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinqigfzy.top/Article/details/gt2yjctgcky.html

Go:   end.Sub(start).Hours()
来源：http://dali.zdqjudy.top/Article/details/gt2bbdqhpgw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.birdmap.top/Article/details/gt2yvogydcj.html

C#:   (end - start).TotalSeconds
来源：http://dali.wangshuangyany.cn/Article/details/gt2iyvcshts.html

[J07] 比较两个日期
来源：http://dali.jqgfzy.top/Article/details/gt2vtsidtev.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gt2ueunrqhe.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhixingplan.top/Article/details/gt2sshdvfwl.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.0kj1m.cn/Article/details/gt2abbrumzv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigufen.top/Article/details/gt2ojlmdypk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.mhx1999.top/Article/details/gt2sbzuuwuu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.c1oappe.top/Article/details/gt2ugwnzpan.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gt2hwnnakor.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gt2buruxnsn.html

[J08] 提取年月日与星期
来源：http://dali.cashguo.top/Article/details/gt2aaajkvdp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sysykeji.top/Article/details/gt2ixcuxmap.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yueranfly.top/Article/details/gt2hsqzetli.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hywenlv.cn/Article/details/gt2durwigfu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigufen.top/Article/details/gt2hntqvole.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.guowangkeji.top/Article/details/gt2xtsjliwz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shangyingyoupin.top/Article/details/gt2jirwzlnd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cucudq.cn/Article/details/gt2ydgvvhmc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rttokjrw.html

[J09] 时区处理
来源：http://dali.aizwys.cn/Article/details/gt2niiunldt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.bjfxy.top/Article/details/gt2zpwocyms.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hfpthk.cn/Article/details/gt2hronvdej.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gt2cpykfiob.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jhmkgleh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.vqdsnc.cn/Article/details/gt2xfwbmhem.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.pycfn.com/Article/details/gt2ttxipnjx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cheryme.top/Article/details/gt2gycxpbdt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ppjwa.cn/Article/details/gt2ubpgcnyh.html

[J10] 取今天 / 本月第一天
来源：http://dali.wangshuangyany.cn/Article/details/gt2baedkydh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.daxiang520.top/Article/details/gt2tjdsgwsz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuxming.cn/Article/details/gt2rtkgrlbi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jiagoushi.top/Article/details/gt2tapjrnfk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.havefunace.top/Article/details/gt2olgwrkei.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yuxming.cn/Article/details/gt2jgdziswn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ppjwa.cn/Article/details/gt2xyclbyko.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2elslrfcz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.redwolf501.top/Article/details/gt2fzvywsbo.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2ehupyrnk.html

K. JSON 与序列化
来源：http://dali.gotoacloud.top/Article/details/gt2aetzccuz.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2bzgogoya.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj20258.top/Article/details/gt2jjjfgznk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sxryk.cn/Article/details/gt2cruuhbem.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gt2wtkjcevb.html

JS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2blfpibbu.html

TS:   JSON.stringify(obj)
来源：http://dali.meibo888.top/Article/details/gt2dakulggo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuanzx.com/Article/details/gt2exvqhknk.html

Go:   json.Marshal(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xejhqnir.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.vqdsnc.cn/Article/details/gt2vqsciixp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tanke756.top/Article/details/gt2zysycvih.html

[K02] JSON 字符串转对象
来源：http://dali.fzhhl.top/Article/details/gt2mbjnzcym.html

Py:   json.loads(s)
来源：http://dali.xziqi.cn/Article/details/gt2awfydpfh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tanke756.top/Article/details/gt2iyjmdidf.html

JS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2shodlytq.html

TS:   JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gt2kcslbqcu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xylfe.cn/Article/details/gt2ytbhhlyx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cfxtjmdr.html

Ruby: JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2dtxuibba.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ricwojju.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.aizwys.cn/Article/details/gt2pznhcgtk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gt2vfaudyqa.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lwicfhyh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gt2otxegjjt.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yongpay.top/Article/details/gt2cvcutcnt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2nskdccwc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tianlin.xyz/Article/details/gt2jhzaduzr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sxryk.cn/Article/details/gt2xqwvtdxh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jyoumei.cn/Article/details/gt2zxjxdqrm.html

[K04] 读取 JSON 文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2htgopnbe.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhixingplan.top/Article/details/gt2xahmfwzg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aizwys.cn/Article/details/gt2wjbajmos.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gzhubu.top/Article/details/gt2bniybtgy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.quarkkingdee.top/Article/details/gt2enjaldwc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qxocqnmu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xziqi.cn/Article/details/gt2sucbkxdo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhixingplan.top/Article/details/gt2dpbhckyx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gt2axxjpdqo.html

[K05] 深拷贝对象
来源：http://dali.wangdashe.top/Article/details/gt2rymyjbpg.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj202588.top/Article/details/gt2fdvmkivs.html

PHP:  unserialize(serialize($obj));
来源：http://dali.svipenyu.cn/Article/details/gt2xiahlxzz.html

JS:   structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2dosugjmr.html

TS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2bvmxmnqq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.svipenyu.cn/Article/details/gt2ltqlxscy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cucudq.cn/Article/details/gt2dtqlxdpu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gzhubu.top/Article/details/gt2ywpqmxer.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.snrcjt.cn/Article/details/gt2mihhpeqi.html

[K06] 解析 URL 查询串
来源：http://dali.nanxuanxn.top/Article/details/gt2wiftiwjp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.daxiang520.top/Article/details/gt2rtwcjylk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxinkj.top/Article/details/gt2xuzpjehc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gt2kgvtgqjj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhixingplan.top/Article/details/gt2rxqruron.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tznvprgs.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gt2buqttsso.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gt2pjzxykpv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gt2ndnmlbol.html

[K07] 进制转换
来源：http://dali.xylfe.cn/Article/details/gt2xvjrzikb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gt2omiwptdg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hammf.cn/Article/details/gt2tfoytryv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gt2yjbtfntn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2sueunydv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gt2xykxdymb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hnqzz.top/Article/details/gt2ybsalzpx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhongyouzk.top/Article/details/gt2pspoqxsj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gt2qxtwjojw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhongyouzk.top/Article/details/gt2uonnanvc.html

Py:   pickle.dumps(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2myuyzrsx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tianlin.xyz/Article/details/gt2wkbmqxvt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.vqdsnc.cn/Article/details/gt2zqrnbplx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cqqwz.cn/Article/details/gt2tvaiixrb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgfzy.top/Article/details/gt2wtyfppqy.html

Go:   encoding/gob
来源：http://dali.yj20258.top/Article/details/gt2oqfyewjw.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2trjlkdoc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhixingplan.top/Article/details/gt2bfgycwjl.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2oadibukq.html

L. 网络请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qmoccife.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2jrgshxel.html

[L01] 发送 GET 请求
来源：http://dali.feifeiyinyue.top/Article/details/gt2qnuopffc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sufxvd.cn/Article/details/gt2fomwwlrq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ydzc1.top/Article/details/gt2xoicpykh.html

JS:   await fetch(url)
来源：http://dali.hnxiangtu.top/Article/details/gt2xzodmokd.html

TS:   await fetch(url)
来源：http://dali.ybcxt.top/Article/details/gt2jmdybrfb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.c1oappe.top/Article/details/gt2hbmukyro.html

Go:   resp, err := http.Get(url)
来源：http://dali.havefunace.top/Article/details/gt2wjjxxdoa.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tian-w.cn/Article/details/gt2qtdfkouf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fzhhl.top/Article/details/gt2iuxdkodi.html

[L02] 发送 POST JSON
来源：http://dali.jqgfzy.top/Article/details/gt2xxlvhvqn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.iojbl.cn/Article/details/gt2qfewbovd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnqzz.top/Article/details/gt2pqllgrwk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hammf.cn/Article/details/gt2bayylgca.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tianlin.xyz/Article/details/gt2teilbnhi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hysaishi.cn/Article/details/gt2ucxohisi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sweek.top/Article/details/gt2gbadivdn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.daxiang520.top/Article/details/gt2pkpyerpu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yangfankeji.com/Article/details/gt2aqrrxjiz.html


<!-- 参考信息 -->