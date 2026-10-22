代发 wailian999

TS:   console.assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gt2chrfmbgn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangshuangyany.cn/Article/details/gt2eznyighc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sxryk.cn/Article/details/gt2cfvoonyx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuanzhike.top/Article/details/gt2zldztlvo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gt2hgecrjrj.html

[H08] 获取错误信息与堆栈
来源：http://dali.yuxming.cn/Article/details/gt2ycvesman.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangdashe.top/Article/details/gt2novtbksm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhixingplan.top/Article/details/gt2saookgjw.html

JS:   e.message;  e.stack
来源：http://dali.xylfe.cn/Article/details/gt2opnsfaea.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sxryk.cn/Article/details/gt2ykjvgjla.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cqqwz.cn/Article/details/gt2dgbyovgj.html

Go:   err.Error()
来源：http://dali.yanxiufei.cn/Article/details/gt2svnukshj.html

Ruby: e.message;  e.backtrace
来源：http://dali.xuanzx.com/Article/details/gt2wyjyijan.html

C#:   e.Message;  e.StackTrace
来源：http://dali.snrcjt.cn/Article/details/gt2hqbbzgpm.html

[H09] 带错误码的异常
来源：http://dali.snrcjt.cn/Article/details/gt2urjkramy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.bjfxy.top/Article/details/gt2nlvvrdqh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.quarkkingdee.top/Article/details/gt2obwsghog.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.redwolf501.top/Article/details/gt2ymewmvwk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.mhx1999.top/Article/details/gt2dhfwjcex.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenzaomai.com/Article/details/gt2snbjkaja.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yangfankeji.com/Article/details/gt2hllxiatx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sysykeji.top/Article/details/gt2piacupfn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cashguo.top/Article/details/gt2zhudwqch.html

[H10] 资源自动释放
来源：http://dali.andypj.xyz/Article/details/gt2ajbdcecx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nwbrower.top/Article/details/gt2dchdemqo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ivvv.top/Article/details/gt2ujkoxayc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tianlin.xyz/Article/details/gt2phllpghz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gt2ouuzrwrr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hywenlv.cn/Article/details/gt2fmzsmuew.html

Go:   defer f.Close()
来源：http://dali.hysaishi.cn/Article/details/gt2typpjnmk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuxming.cn/Article/details/gt2cbjlrjps.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2djcmfwyl.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2dztocarf.html

I. 正则表达式
来源：http://dali.gzhubu.top/Article/details/gt2kszhglpj.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2hzdszyix.html

[I01] 判断是否匹配
来源：http://dali.xuanzx.com/Article/details/gt2xgmabbfw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenzaomai.com/Article/details/gt2wgigfjuh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jianghu66.top/Article/details/gt2pwotqokj.html

JS:   /\d+/.test(s)
来源：http://dali.tanke756.top/Article/details/gt2zxnthupv.html

TS:   /\d+/.test(s)
来源：http://dali.gogol.net.cn/Article/details/gt2ugtctjgx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.c1oappe.top/Article/details/gt2pwexqxfo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ppjwa.cn/Article/details/gt2fdvmwnts.html

Ruby: s.match?(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gt2jsmdqlyt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnxiangtu.top/Article/details/gt2vvyttwgu.html

[I02] 提取所有匹配
来源：http://dali.wangdashe.top/Article/details/gt2ymrktkzl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2skpebpap.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sysykeji.top/Article/details/gt2oosjisox.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.9152youxi.cn/Article/details/gt2hzmqoabv.html

TS:   s.match(/\d+/g)
来源：http://dali.jyoumei.cn/Article/details/gt2mmmnonww.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yuxming.cn/Article/details/gt2ussvaczh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gt2tosppwce.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oyikfoic.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sweek.top/Article/details/gt2mpyqsnbv.html

[I03] 提取捕获分组
来源：http://dali.yanxiufei.cn/Article/details/gt2urosomah.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.wangdashe.top/Article/details/gt2jobpwwot.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.dashuyun.cn/Article/details/gt2vicorxbh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.iojbl.cn/Article/details/gt2odvwluyi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xinyue.icu/Article/details/gt2rqsbohzx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nanxuanxn.top/Article/details/gt2yzzsczju.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2budpazoh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sweek.top/Article/details/gt2vwwoknuu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jiagoushi.top/Article/details/gt2apupvzsi.html

[I04] 正则替换
来源：http://dali.tian-w.cn/Article/details/gt2obrfgrbo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gaohongyu789.top/Article/details/gt2pokkuieb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.havefunace.top/Article/details/gt2gtmluahi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.meibo888.top/Article/details/gt2mgdiretg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kxtheflv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gt2bhbzmzyj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hammf.cn/Article/details/gt2cwhtmgis.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj202588.top/Article/details/gt2izsviizk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.quarkkingdee.top/Article/details/gt2mbwmehjd.html

[I05] 按正则拆分
来源：http://dali.snrcjt.cn/Article/details/gt2aigqhnri.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yangfankeji.com/Article/details/gt2zufscfbo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2trmeyxzx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gt2nuhrqnjh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gt2sdpwfxuf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.feifeiyinyue.top/Article/details/gt2veyrngxn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jiagoushi.top/Article/details/gt2cukcjmww.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rznmarsl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aibaodan.cn/Article/details/gt2jxrlmdja.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.wangshuangyany.cn/Article/details/gt2umjcfhti.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nihqpzvx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.snrcjt.cn/Article/details/gt2vkafvwlo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cqqwz.cn/Article/details/gt2jlftorby.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhongyouzk.top/Article/details/gt2vbqwjtjy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gt2rmdgwygv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ehwqpu.com/Article/details/gt2ucnctsna.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ybcxt.top/Article/details/gt2raikwccs.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nrqjpxrw.html

[I07] 忽略大小写与多行模式
来源：http://dali.gzhubu.top/Article/details/gt2yeyzgedg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.svipenyu.cn/Article/details/gt2rhczxdyl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gt2gpgmtejg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.guannengcc.top/Article/details/gt2xgiyiika.html

TS:   /error/gim
来源：http://dali.sufxvd.cn/Article/details/gt2gmmtxbbq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2sajxexqr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dashuyun.cn/Article/details/gt2tddwqagy.html

Ruby: s.scan(/error/i)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nywlmzyj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zycfv.cn/Article/details/gt2ugxgqaqv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xziqi.cn/Article/details/gt2oiuyibwk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gzhubu.top/Article/details/gt2btwzbdev.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gt2rwgfzvbi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnqzz.top/Article/details/gt2hgcipqnc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2inufsdhb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.quarkkingdee.top/Article/details/gt2hdajnuzc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.smart0.xyz/Article/details/gt2hgavzjrw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shzxlz.cn/Article/details/gt2rnznoqxt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.guannengcc.top/Article/details/gt2oldwlhjb.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2vacxhmpo.html

J. 日期与时间
来源：http://dali.andypj.xyz/Article/details/gt2yhjfocqe.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2exolnuhs.html

[J01] 获取当前时间
来源：http://dali.meibo888.top/Article/details/gt2ndewjlrk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.guowangkeji.top/Article/details/gt2gnragsks.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zycfv.cn/Article/details/gt2mtoocwst.html

JS:   new Date();  Date.now()
来源：http://dali.yj202588.top/Article/details/gt2ipgwzarz.html

TS:   new Date();  Date.now()
来源：http://dali.cashguo.top/Article/details/gt2sppbovwp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinqigufen.top/Article/details/gt2wgoubqkv.html

Go:   time.Now()
来源：http://dali.zhengqikj.top/Article/details/gt2byeiqxrs.html

Ruby: Time.now
来源：http://dali.dashuyun.cn/Article/details/gt2pbdmgdkl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.redwolf501.top/Article/details/gt2fyxjtgzq.html

[J02] 格式化输出
来源：http://dali.hysaishi.cn/Article/details/gt2enuxijhc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.vqdsnc.cn/Article/details/gt2zfugjuhp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yangfankeji.com/Article/details/gt2ifbpmpsg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhengqikj.top/Article/details/gt2tqbhrwkc.html

TS:   d.toISOString()
来源：http://dali.yanxiufei.cn/Article/details/gt2ppixyxvc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xuetiantiany.cn/Article/details/gt2pzhrjzej.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aljhohfn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gt2eqwmbeqk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhoulong.xyz/Article/details/gt2eanveppa.html

[J03] 字符串解析为日期
来源：http://dali.jyoumei.cn/Article/details/gt2zelcfwzq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.guannengcc.top/Article/details/gt2gikuphjw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yuxming.cn/Article/details/gt2mypydhir.html

JS:   new Date("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gt2xryptqwz.html

TS:   new Date("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gt2hgbodgrj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gt2vcoqbfdp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gt2tjmrzjcp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ziosijfc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.aibaodan.cn/Article/details/gt2djdghbhf.html

[J04] 时间戳与日期互转
来源：http://dali.tianlin.xyz/Article/details/gt2tatxxskd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cirxneod.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.svipenyu.cn/Article/details/gt2ksphlegd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.iojbl.cn/Article/details/gt2sqqngqxf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.guowangkeji.top/Article/details/gt2guiuadhi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ydzc1.top/Article/details/gt2gbgkkujr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2jfcghkim.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgufenzy.top/Article/details/gt2mhncwxxy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gt2sfmcyxck.html

[J05] 时间加减（加 7 天）
来源：http://dali.jyoumei.cn/Article/details/gt2btunwzep.html

Py:   now + timedelta(days=7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qsfxyghb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.dashuyun.cn/Article/details/gt2qbvpbuyu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yvedp.cn/Article/details/gt2zhkpxqdg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ikrnlaln.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fzhhl.top/Article/details/gt2isiqtebq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sxryk.cn/Article/details/gt2rnimuutf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jlsjyb.cn/Article/details/gt2uxoglqrg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jianghu66.top/Article/details/gt2ayntysrm.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tskchkgo.html

Py:   (end - start).total_seconds()
来源：http://dali.fengsongda.top/Article/details/gt2tqamovkx.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhengqikj.top/Article/details/gt2gtbukefk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj202588.top/Article/details/gt2aaffrmaa.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gt2kuaolhmi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.daxiang520.top/Article/details/gt2uqwghkdy.html

Go:   end.Sub(start).Hours()
来源：http://dali.bjfxy.top/Article/details/gt2wqcruxha.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shangyingyoupin.top/Article/details/gt2lpzagckn.html

C#:   (end - start).TotalSeconds
来源：http://dali.zdqjudy.top/Article/details/gt2fmxopoqk.html

[J07] 比较两个日期
来源：http://dali.shzxlz.cn/Article/details/gt2bgpjrudm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gt2bnspsfta.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnqzz.top/Article/details/gt2zbnplham.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gt2pquwgnjh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gt2kfdhtvoe.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hywenlv.cn/Article/details/gt2vgqmyfro.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jiagoushi.top/Article/details/gt2yyoaxdsf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gt2bjlixanu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gt2fcgkurqm.html

[J08] 提取年月日与星期
来源：http://dali.zhoulong.xyz/Article/details/gt2rlcxmwrh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gotoacloud.top/Article/details/gt2urvddmdz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.smart0.xyz/Article/details/gt2bafyrpbh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tianlin.xyz/Article/details/gt2canrdmhr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gotoacloud.top/Article/details/gt2izhgswty.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tian-w.cn/Article/details/gt2fjzbjupp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cucudq.cn/Article/details/gt2bzjkgpwc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ppjwa.cn/Article/details/gt2uofjpuml.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.snrcjt.cn/Article/details/gt2pzzykyzi.html

[J09] 时区处理
来源：http://dali.yvedp.cn/Article/details/gt2uwtdjfkg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yongpay.top/Article/details/gt2xjfbpeyq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dashuyun.cn/Article/details/gt2hgtyzvkf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gt2cckbyjmt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cucudq.cn/Article/details/gt2lhixcecg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj202588.top/Article/details/gt2udvgwvab.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hysaishi.cn/Article/details/gt2ndnmmdwn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.birdmap.top/Article/details/gt2pazclmoc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vokbotjq.html

[J10] 取今天 / 本月第一天
来源：http://dali.yonumen.top/Article/details/gt2nodgwjif.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yueranfly.top/Article/details/gt2dniemiwn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jyoumei.cn/Article/details/gt2fqjibmfz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daxiang520.top/Article/details/gt2fbvrxriv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj202588.top/Article/details/gt2whrrbbkr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gogol.net.cn/Article/details/gt2dplvmzbx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cqqwz.cn/Article/details/gt2egosywfb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dianchejie.cn/Article/details/gt2mdmtsgej.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hywenlv.cn/Article/details/gt2pdesiggs.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2iuspieag.html

K. JSON 与序列化
来源：http://dali.kuanghao11.cn/Article/details/gt2grlkxvtc.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2gmmqswsw.html

[K01] 对象转 JSON 字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2gybsaxfv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gt2hbdobnog.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gt2blgklgps.html

JS:   JSON.stringify(obj)
来源：http://dali.bjfxy.top/Article/details/gt2lioxurmo.html

TS:   JSON.stringify(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ulajrnag.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhengqikj.top/Article/details/gt2cbmbgcqf.html

Go:   json.Marshal(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2moeeisya.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cheryme.top/Article/details/gt2nkqfggwy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2mknrqitk.html

[K02] JSON 字符串转对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kvytsodw.html

Py:   json.loads(s)
来源：http://dali.daxiang520.top/Article/details/gt2mnyjdxwz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jyoumei.cn/Article/details/gt2ewvimeld.html

JS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xhmjayag.html

TS:   JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qzqhrqhv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jiagoushi.top/Article/details/gt2hqiugexc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yonumen.top/Article/details/gt2oaicpkgh.html

Ruby: JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gt2rkllvajk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.meibo888.top/Article/details/gt2qbyuvdig.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.haohaochexian.top/Article/details/gt2opzgrqrx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ehwqpu.com/Article/details/gt2izqnaigh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gaohongyu789.top/Article/details/gt2accdwwtp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gt2jpyezksd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yangfankeji.com/Article/details/gt2gxfsmtif.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2iiltzmgk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuxming.cn/Article/details/gt2lgsojdjw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tian-w.cn/Article/details/gt2ufhvrxvi.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cdnleiting.top/Article/details/gt2gqebtoxd.html

[K04] 读取 JSON 文件
来源：http://dali.shuidangran.top/Article/details/gt2loqdcjmd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj20258.top/Article/details/gt2akitctfv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hywenlv.cn/Article/details/gt2vmxiupgr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2fezyufdn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fengsongda.top/Article/details/gt2hojxfofo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guowangkeji.top/Article/details/gt2yzhhofkn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.iojbl.cn/Article/details/gt2fmnbiacb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.vqdsnc.cn/Article/details/gt2wwgdukeu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hfpthk.cn/Article/details/gt2spjvzrxp.html

[K05] 深拷贝对象
来源：http://dali.hywenlv.cn/Article/details/gt2adgiclpk.html

Py:   copy.deepcopy(obj)
来源：http://dali.andypj.xyz/Article/details/gt2szbspxxy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sweek.top/Article/details/gt2nitkyypx.html

JS:   structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gt2ekdenlbq.html

TS:   structuredClone(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kejyngmt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nanxinkj.top/Article/details/gt2vgeixfqg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ppjwa.cn/Article/details/gt2ymjrfqfu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jlsjyb.cn/Article/details/gt2jqvktlrb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnqzz.top/Article/details/gt2pquflzoh.html

[K06] 解析 URL 查询串
来源：http://dali.xuetiantiany.cn/Article/details/gt2fsjwwerk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.fzhhl.top/Article/details/gt2zbjcrlml.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.svipenyu.cn/Article/details/gt2xgffnsbw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenzaomai.com/Article/details/gt2pdkfnzsw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jlsjyb.cn/Article/details/gt2bfpvlequ.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hysaishi.cn/Article/details/gt2fbwzkphm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gt2xsqregvm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gt2qeajckpl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gt2gwwfnxzu.html

[K07] 进制转换
来源：http://dali.316326.xyz/Article/details/gt2sqhgobug.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gt2wcuuwlia.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yanxiufei.cn/Article/details/gt2dvdrlcxi.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kymxnkhx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nbirfjvw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cfpfpqle.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yongpay.top/Article/details/gt2sxlckyvr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yuanzhike.top/Article/details/gt2ohdovpsd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gt2eghgaofe.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.quarkkingdee.top/Article/details/gt2hcgwqwuy.html

Py:   pickle.dumps(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2kxdldfbe.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yanxiufei.cn/Article/details/gt2xvqyiwco.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jqgfzy.top/Article/details/gt2ekajvrrl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.wangshuangyany.cn/Article/details/gt2yvnldfug.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sufxvd.cn/Article/details/gt2yctmaesl.html

Go:   encoding/gob
来源：http://dali.hfpthk.cn/Article/details/gt2gyyjtize.html

Ruby: Marshal.dump(obj)
来源：http://dali.cashguo.top/Article/details/gt2inpicwos.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hammf.cn/Article/details/gt2cquyflbo.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2ygbamrix.html

L. 网络请求
来源：http://dali.dianchejie.cn/Article/details/gt2cpyekrba.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2eakseyma.html

[L01] 发送 GET 请求
来源：http://dali.jyoumei.cn/Article/details/gt2uvypqynz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xuetiantiany.cn/Article/details/gt2ucxuzzdo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.aizwys.cn/Article/details/gt2aazlggoo.html

JS:   await fetch(url)
来源：http://dali.aizwys.cn/Article/details/gt2fngpgyak.html

TS:   await fetch(url)
来源：http://dali.gotoacloud.top/Article/details/gt2ztkerfke.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jyoumei.cn/Article/details/gt2ndxifofw.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgfzy.top/Article/details/gt2ytrypuve.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ydzc1.top/Article/details/gt2qrvzdqxj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yuanzhike.top/Article/details/gt2tjklhpwv.html

[L02] 发送 POST JSON
来源：http://dali.quarkkingdee.top/Article/details/gt2kxaioqgd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.fengsongda.top/Article/details/gt2yljroyxs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ehwqpu.com/Article/details/gt2izdvdppa.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.vqdsnc.cn/Article/details/gt2hbpulcsk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tian-w.cn/Article/details/gt2obfufhuy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.andypj.xyz/Article/details/gt2gqbdwsrz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.feifeiyinyue.top/Article/details/gt2mkrmgzqj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.aizwys.cn/Article/details/gt2qwylmuwo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.quarkkingdee.top/Article/details/gt2hkebrwsw.html

[L03] 设置自定义请求头
来源：http://dali.zdqjudy.top/Article/details/gt2umkrgsys.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinqigufen.top/Article/details/gt2jpcutbfh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dashuyun.cn/Article/details/gt2zdmkgegl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hysaishi.cn/Article/details/gt2asplnaaa.html


<!-- 参考信息 -->